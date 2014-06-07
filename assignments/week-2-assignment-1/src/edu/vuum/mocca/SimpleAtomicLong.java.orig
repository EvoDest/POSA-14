// Import the necessary Java synchronization and scheduling classes.

package edu.vuum.mocca;

import java.util.concurrent.locks.ReentrantReadWriteLock;

/**
 * @class SimpleAtomicLong
 *
 * @brief This class implements a subset of the
 *        java.util.concurrent.atomic.SimpleAtomicLong class using a
 *        ReentrantReadWriteLock to illustrate how they work.
 */
class SimpleAtomicLong
{
    /**
     * The value that's manipulated atomically via the methods.
     */
    private long mValue;


    /**
     * The ReentrantReadWriteLock used to serialize access to mValue.
     */
<<<<<<< HEAD
    // TODO - add the implementation
=======

    // TODO -- you fill in here by replacing the null with an
    // initialization of ReentrantReadWriteLock.
    private ReentrantReadWriteLock mRWLock = new ReentrantReadWriteLock();
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1

    /**
     * Creates a new SimpleAtomicLong with the given initial value.
     */
<<<<<<< HEAD
    public SimpleAtomicLong(long initialValue) {
        // TODO - you fill in here
=======
    public SimpleAtomicLong(long initialValue)
    {
        // TODO -- you fill in here
    	mValue = initialValue;
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1
    }

    /**
     * @brief Gets the current value
     * 
     * @returns The current value
     */
<<<<<<< HEAD
    public long get() {
        // TODO - you fill in here
=======
    public long get()
    {
        // TODO -- you fill in here

		long value = 0;
		
    	mRWLock.readLock().lock();
    	
    	try {
    		value = mValue;
    	} catch(Exception ex) {
    		System.out.println(ex.getMessage());
    	} finally {
            mRWLock.readLock().unlock();
    	}

        return value;
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1
    }

    /**
     * @brief Atomically decrements by one the current value
     *
     * @returns the updated value
     */
<<<<<<< HEAD
    public long decrementAndGet() {
        // TODO - you fill in here
=======
    public long decrementAndGet()
    {
        // TODO -- you fill in here
        mRWLock.writeLock().lock();
        
        try{
        	--mValue;
        } catch(Exception ex) {
    		System.out.println(ex.getMessage());
    	} finally {
        	mRWLock.writeLock().unlock();
        }
        
        long value = get();
        
        return value;
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1
    }

    /**
     * @brief Atomically increments by one the current value
     *
     * @returns the previous value
     */
<<<<<<< HEAD
    public long getAndIncrement() {
        // TODO - you fill in here
=======
    public long getAndIncrement()
    {
        long value = get();

        // TODO -- you fill in here
        mRWLock.writeLock().lock();
        
        try{
        	++mValue;
        } catch(Exception ex) {
    		System.out.println(ex.getMessage());
    	} finally {
        	mRWLock.writeLock().unlock();
        }
        
        return value;
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1
    }

    /**
     * @brief Atomically decrements by one the current value
     *
     * @returns the previous value
     */
<<<<<<< HEAD
    public long getAndDecrement() {
        // TODO - you fill in here
=======
    public long getAndDecrement()
    {
        long value = get();

        // TODO -- you fill in here
        mRWLock.writeLock().lock();
        
        try {
        	--mValue;
        } catch(Exception ex) {
    		System.out.println(ex.getMessage());
    	} finally {
        	mRWLock.writeLock().unlock();
        }
        
        return value;
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1
    }

    /**
     * @brief Atomically increments by one the current value
     *
     * @returns the updated value
     */
<<<<<<< HEAD
    public long incrementAndGet() {
        // TODO - you fill in here
=======
    public long incrementAndGet()
    {
        // TODO -- you fill in here
        
    	mRWLock.writeLock().lock();
        
    	try {
    		++mValue;
    	} catch(Exception ex) {
    		System.out.println(ex.getMessage());
    	} finally {
    		mRWLock.writeLock().unlock();
    	}
    	
        long value = get();

        return value;
>>>>>>> Updates for week-1-assignment-0 and week-2-assignment-1
    }
}
